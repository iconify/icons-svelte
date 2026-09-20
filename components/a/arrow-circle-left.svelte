<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-elkab4b.css';
import '../../css/a/a17nx6bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-elkab4b"/><path class="a17nx6bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:arrow-circle-left" {...props}></Icon>
