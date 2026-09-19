<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhqe6ib7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhqe6ib7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-grin-wide" {...props}></Icon>
