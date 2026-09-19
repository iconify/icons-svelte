<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_cpnh_xd.css';
import '../../css/h/hqrdqe__q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_cpnh_xd"/><rect class="hqrdqe__q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:checkbox-outline" {...props}></Icon>
