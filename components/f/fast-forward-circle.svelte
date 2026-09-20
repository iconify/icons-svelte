<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo2b50bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fo2b50bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fast-forward-circle" {...props}></Icon>
