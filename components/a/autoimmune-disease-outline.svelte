<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-cmf8bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h-cmf8bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:autoimmune-disease-outline" {...props}></Icon>
