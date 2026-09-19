<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snn4eibbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="snn4eibbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mac-command" {...props}></Icon>
