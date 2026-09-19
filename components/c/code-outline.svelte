<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qprcm74ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qprcm74ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:code-outline" {...props}></Icon>
