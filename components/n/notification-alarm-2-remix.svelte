<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzd5e6bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hzd5e6bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:notification-alarm-2-remix" {...props}></Icon>
