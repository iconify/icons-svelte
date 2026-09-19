<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm52ebcgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rm52ebcgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:desktop-app2x-outline" {...props}></Icon>
