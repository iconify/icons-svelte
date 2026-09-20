<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odawy8e3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="odawy8e3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:grid-squares" {...props}></Icon>
