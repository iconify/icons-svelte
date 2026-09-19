<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4v10i-vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i4v10i-vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cochlear-implant2x-outline" {...props}></Icon>
