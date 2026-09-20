<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmzr89wwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmzr89wwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cake-line" {...props}></Icon>
