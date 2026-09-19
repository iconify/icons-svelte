<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kytgmnkcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kytgmnkcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-sleet-fill" {...props}></Icon>
