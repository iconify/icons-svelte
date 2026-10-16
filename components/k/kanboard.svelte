<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqamdbc7e.css';
import '../../css/n/nmg5wwk4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":144,"height":144};
const content = `<path class="zqamdbc7e"/><path class="nmg5wwk4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kanboard" {...props}></Icon>
