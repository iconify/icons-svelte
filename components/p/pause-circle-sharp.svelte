<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx4_4o47q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vx4_4o47q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pause-circle-sharp" {...props}></Icon>
