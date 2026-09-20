<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur-8hrb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ur-8hrb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:alert-fill-16" {...props}></Icon>
