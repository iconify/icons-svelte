<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc19cipac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc19cipac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-line" {...props}></Icon>
