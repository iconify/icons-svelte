<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm3_yrfqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zm3_yrfqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:empty" {...props}></Icon>
