<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts93_uoga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ts93_uoga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:construction-cone" {...props}></Icon>
