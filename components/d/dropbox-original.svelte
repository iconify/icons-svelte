<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0kd4mg4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v0kd4mg4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dropbox-original" {...props}></Icon>
