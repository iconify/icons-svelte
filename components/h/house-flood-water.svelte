<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwvf1sbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vwvf1sbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-flood-water" {...props}></Icon>
