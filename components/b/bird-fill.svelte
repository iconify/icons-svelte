<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amo84csgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amo84csgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bird-fill" {...props}></Icon>
