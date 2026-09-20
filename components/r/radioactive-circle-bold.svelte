<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvwl8n50p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvwl8n50p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:radioactive-circle-bold" {...props}></Icon>
