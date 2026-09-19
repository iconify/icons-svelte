<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arq7f-vxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="arq7f-vxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:html5-shield" {...props}></Icon>
