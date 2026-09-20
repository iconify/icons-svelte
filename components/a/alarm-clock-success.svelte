<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuw0tqbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yuw0tqbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:alarm-clock-success" {...props}></Icon>
