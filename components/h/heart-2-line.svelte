<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd2lh0b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd2lh0b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heart-2-line" {...props}></Icon>
