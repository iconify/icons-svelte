<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxgwi8bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bxgwi8bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:octagon-48" {...props}></Icon>
