<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqd_l2b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqd_l2b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:caret-left" {...props}></Icon>
