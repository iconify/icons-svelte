<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjo07wwqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjo07wwqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-hold-linear-out-filled" {...props}></Icon>
