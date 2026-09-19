<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl-az0bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vl-az0bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:plug" {...props}></Icon>
