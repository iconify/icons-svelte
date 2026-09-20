<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwx5zpbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rwx5zpbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:marker-stroked" {...props}></Icon>
