<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j55ox3b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j55ox3b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mountain-peak-filled" {...props}></Icon>
