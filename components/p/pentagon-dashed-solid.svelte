<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6wxn2day.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6wxn2day"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pentagon-dashed-solid" {...props}></Icon>
