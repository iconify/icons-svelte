<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re6c-mj_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re6c-mj_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:axis-x-arrow-lock" {...props}></Icon>
