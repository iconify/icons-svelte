<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfwhivbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xfwhivbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:hammer2" {...props}></Icon>
