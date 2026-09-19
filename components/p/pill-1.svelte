<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpzch7b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cpzch7b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pill-1" {...props}></Icon>
