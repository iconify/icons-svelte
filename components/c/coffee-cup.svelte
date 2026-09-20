<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8od9obqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h8od9obqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:coffee-cup" {...props}></Icon>
