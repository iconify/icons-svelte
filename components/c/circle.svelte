<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxe6n8b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qxe6n8b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:circle" {...props}></Icon>
