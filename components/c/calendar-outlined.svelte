<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0r6koz6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r0r6koz6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:calendar-outlined" {...props}></Icon>
