<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh_t_956l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="dh_t_956l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:border-none" {...props}></Icon>
