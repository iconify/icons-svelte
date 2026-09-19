<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8jcx0zgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8jcx0zgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:left-arrow-square" {...props}></Icon>
