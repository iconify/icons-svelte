<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpw970bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpw970bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:menu-right" {...props}></Icon>
