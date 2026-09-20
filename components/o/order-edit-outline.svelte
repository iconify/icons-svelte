<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu25hacoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eu25hacoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:order-edit-outline" {...props}></Icon>
