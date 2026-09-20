<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqs725hfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqs725hfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:esphome" {...props}></Icon>
