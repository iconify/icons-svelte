<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8q_w5_vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y8q_w5_vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:calendar" {...props}></Icon>
