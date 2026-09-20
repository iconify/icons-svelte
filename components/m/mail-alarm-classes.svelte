<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwbusqb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wwbusqb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mail-alarm-classes" {...props}></Icon>
