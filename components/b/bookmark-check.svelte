<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unmjk69jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unmjk69jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bookmark-check" {...props}></Icon>
