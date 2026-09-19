<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiihi1bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hiihi1bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:phone" {...props}></Icon>
