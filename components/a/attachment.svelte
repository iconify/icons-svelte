<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tat62hbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tat62hbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:attachment" {...props}></Icon>
