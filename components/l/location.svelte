<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moujm4bxk.css';
import '../../css/y/yoimegbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moujm4bxk"/><path class="yoimegbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location" {...props}></Icon>
