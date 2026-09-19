<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm2yf_bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fm2yf_bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bin2" {...props}></Icon>
