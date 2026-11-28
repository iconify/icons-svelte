<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhl4ykefx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhl4ykefx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-down-right" {...props}></Icon>
