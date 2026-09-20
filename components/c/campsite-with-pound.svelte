<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms_-knb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ms_-knb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-with-pound" {...props}></Icon>
