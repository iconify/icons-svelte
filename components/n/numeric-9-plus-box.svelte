<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duab7-boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duab7-boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-9-plus-box" {...props}></Icon>
