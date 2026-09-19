<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8h4xabsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l8h4xabsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:forest-outline" {...props}></Icon>
