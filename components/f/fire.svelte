<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8wpkjq1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8wpkjq1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fire" {...props}></Icon>
