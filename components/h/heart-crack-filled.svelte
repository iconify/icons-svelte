<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8iq1hkzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8iq1hkzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-crack-filled" {...props}></Icon>
