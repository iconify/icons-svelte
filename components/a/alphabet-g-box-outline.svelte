<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st3e-o8vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st3e-o8vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-g-box-outline" {...props}></Icon>
