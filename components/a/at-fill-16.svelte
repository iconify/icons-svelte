<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuidfv4uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iuidfv4uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:at-fill-16" {...props}></Icon>
