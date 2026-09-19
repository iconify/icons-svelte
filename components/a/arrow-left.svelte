<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0o2q1bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s0o2q1bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-left" {...props}></Icon>
