<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shs33w4vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="shs33w4vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:device-bug" {...props}></Icon>
