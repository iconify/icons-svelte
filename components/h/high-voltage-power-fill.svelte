<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh8ynxhnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh8ynxhnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:high-voltage-power-fill" {...props}></Icon>
