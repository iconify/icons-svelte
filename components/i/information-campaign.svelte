<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_m39d9gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k_m39d9gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:information-campaign" {...props}></Icon>
