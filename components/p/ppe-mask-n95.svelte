<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k73fajykc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k73fajykc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-mask-n95" {...props}></Icon>
