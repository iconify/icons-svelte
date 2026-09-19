<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g82dpbb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g82dpbb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mosquito-collection-outline" {...props}></Icon>
