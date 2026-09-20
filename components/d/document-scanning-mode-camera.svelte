<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_kn1vbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_kn1vbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:document-scanning-mode-camera" {...props}></Icon>
