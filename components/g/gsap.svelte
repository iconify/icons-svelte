<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz3vwebsj.css';
import '../../css/l/l2g7ibbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz3vwebsj"/><path class="l2g7ibbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:gsap" {...props}></Icon>
