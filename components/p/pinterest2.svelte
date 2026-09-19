<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grhpbbc3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="grhpbbc3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:pinterest2" {...props}></Icon>
