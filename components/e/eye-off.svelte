<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v14bsqblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v14bsqblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:eye-off" {...props}></Icon>
