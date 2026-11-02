<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkee8wzft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkee8wzft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:braces-fill" {...props}></Icon>
