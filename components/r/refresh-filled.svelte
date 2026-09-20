<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1adhfb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v1adhfb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:refresh-filled" {...props}></Icon>
