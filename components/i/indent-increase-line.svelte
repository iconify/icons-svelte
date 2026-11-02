<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeq25k99a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeq25k99a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:indent-increase-line" {...props}></Icon>
