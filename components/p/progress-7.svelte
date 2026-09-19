<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtc0jqpcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="rtc0jqpcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:progress-7" {...props}></Icon>
