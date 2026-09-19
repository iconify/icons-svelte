<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sve_pcibh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sve_pcibh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:magic-wand2x-outline" {...props}></Icon>
