<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7r0-s_tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7r0-s_tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:discount-filled" {...props}></Icon>
