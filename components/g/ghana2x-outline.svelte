<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycr3-ac1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ycr3-ac1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ghana2x-outline" {...props}></Icon>
