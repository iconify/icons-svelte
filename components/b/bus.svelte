<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lww32bc-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lww32bc-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bus" {...props}></Icon>
