<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yat57cxyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yat57cxyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:euro" {...props}></Icon>
