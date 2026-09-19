<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezgh_-b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ezgh_-b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:enzyme" {...props}></Icon>
