<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo2057bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bo2057bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alarmpi-dark" {...props}></Icon>
