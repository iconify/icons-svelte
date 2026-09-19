<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwn5_d3cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwn5_d3cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:a-arrow-up" {...props}></Icon>
