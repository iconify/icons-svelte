<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc02_2oll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rc02_2oll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-up-outline" {...props}></Icon>
