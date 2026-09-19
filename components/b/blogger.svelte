<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzv79um5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lzv79um5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:blogger" {...props}></Icon>
