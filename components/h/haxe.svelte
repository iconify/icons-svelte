<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzo2hibyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gzo2hibyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:haxe" {...props}></Icon>
