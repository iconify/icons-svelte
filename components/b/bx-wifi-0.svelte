<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l97nb-quh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="l97nb-quh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-wifi-0" {...props}></Icon>
