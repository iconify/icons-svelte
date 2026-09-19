<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_gbwm76b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w_gbwm76b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:o2x-outline" {...props}></Icon>
