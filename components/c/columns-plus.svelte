<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdfx0ab_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdfx0ab_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:columns-plus" {...props}></Icon>
