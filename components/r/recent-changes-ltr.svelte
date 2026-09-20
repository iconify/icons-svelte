<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arx7bg38m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="arx7bg38m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:recent-changes-ltr" {...props}></Icon>
