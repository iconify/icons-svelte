<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcn5yl7de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":780,"height":621};
const content = `<path class="vcn5yl7de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:college" {...props}></Icon>
