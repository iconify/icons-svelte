<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhq6-qa5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nhq6-qa5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:embassy" {...props}></Icon>
