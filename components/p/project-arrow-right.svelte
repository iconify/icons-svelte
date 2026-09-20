<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqvyd9bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqvyd9bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:project-arrow-right" {...props}></Icon>
