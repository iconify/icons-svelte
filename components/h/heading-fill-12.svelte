<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9mcn14ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s9mcn14ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:heading-fill-12" {...props}></Icon>
