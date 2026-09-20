<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaop-ogzu.css';
import '../../css/w/w8tcc-b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gaop-ogzu"/><path class="w8tcc-b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-medical-notes" {...props}></Icon>
