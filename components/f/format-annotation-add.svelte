<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4u8blsoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4u8blsoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-annotation-add" {...props}></Icon>
