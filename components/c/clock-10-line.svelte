<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm-dfbcsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm-dfbcsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-10-line" {...props}></Icon>
