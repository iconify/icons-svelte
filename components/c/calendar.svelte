<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kam2ibkwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kam2ibkwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:calendar" {...props}></Icon>
