<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl1hntrbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cl1hntrbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cross-country-motorcycle2x-outline" {...props}></Icon>
