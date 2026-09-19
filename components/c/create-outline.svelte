<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yruwzs0qg.css';
import '../../css/x/xv8czdbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yruwzs0qg"/><path class="xv8czdbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:create-outline" {...props}></Icon>
