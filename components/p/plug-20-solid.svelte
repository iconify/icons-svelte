<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h21mulwpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h21mulwpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:plug-20-solid" {...props}></Icon>
