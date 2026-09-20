<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo82r35gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo82r35gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-heart-line" {...props}></Icon>
