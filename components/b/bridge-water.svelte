<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dudglib1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="dudglib1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bridge-water" {...props}></Icon>
