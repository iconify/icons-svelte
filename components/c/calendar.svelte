<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3hnvlbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="u3hnvlbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:calendar" {...props}></Icon>
