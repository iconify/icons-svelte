<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo_2k_dtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo_2k_dtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-tiger-solid" {...props}></Icon>
