<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsgqcgbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsgqcgbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-list-group" {...props}></Icon>
