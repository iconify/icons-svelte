<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxmxzghrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxmxzghrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-pdf-outline" {...props}></Icon>
