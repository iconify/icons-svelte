<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og00ut_0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og00ut_0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-vibration-line" {...props}></Icon>
