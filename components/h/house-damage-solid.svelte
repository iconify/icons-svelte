<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o43r2_blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o43r2_blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:house-damage-solid" {...props}></Icon>
