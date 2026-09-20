<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylw5qp-cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylw5qp-cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:reactive-resume" {...props}></Icon>
