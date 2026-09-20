<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy-_ygbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy-_ygbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrange-send-to-back" {...props}></Icon>
