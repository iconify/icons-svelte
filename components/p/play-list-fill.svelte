<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g432uxb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g432uxb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-list-fill" {...props}></Icon>
