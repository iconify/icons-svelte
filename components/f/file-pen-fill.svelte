<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcr3n5mdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcr3n5mdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-pen-fill" {...props}></Icon>
