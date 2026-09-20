<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7auwh65h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7auwh65h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dossier-fill" {...props}></Icon>
