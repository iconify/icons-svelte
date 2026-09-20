<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsu_6q6po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsu_6q6po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-unfold-3-line" {...props}></Icon>
