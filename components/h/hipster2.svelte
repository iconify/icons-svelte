<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtb_bmmkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rtb_bmmkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:hipster2" {...props}></Icon>
