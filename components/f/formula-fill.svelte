<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc05s8evs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc05s8evs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:formula-fill" {...props}></Icon>
