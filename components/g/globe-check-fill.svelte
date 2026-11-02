<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yze8-eekk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yze8-eekk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-check-fill" {...props}></Icon>
