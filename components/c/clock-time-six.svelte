<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmaogdb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmaogdb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-six" {...props}></Icon>
