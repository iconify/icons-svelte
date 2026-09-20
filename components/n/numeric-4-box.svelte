<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4s-skbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4s-skbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-4-box" {...props}></Icon>
