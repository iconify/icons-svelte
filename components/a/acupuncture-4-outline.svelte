<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccjkfxb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ccjkfxb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:acupuncture-4-outline" {...props}></Icon>
