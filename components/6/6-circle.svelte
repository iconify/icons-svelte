<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe3z6rwqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fe3z6rwqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:6-circle" {...props}></Icon>
