<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5ym-lbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ym-lbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-fill" {...props}></Icon>
