<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxq44iahj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxq44iahj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bookmark-plus" {...props}></Icon>
