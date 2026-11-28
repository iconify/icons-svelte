<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql3-lpzya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql3-lpzya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hexagon-half-solid" {...props}></Icon>
