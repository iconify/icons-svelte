<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t23k8na6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t23k8na6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mixed-reality" {...props}></Icon>
