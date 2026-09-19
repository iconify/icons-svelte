<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2v2x5blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i2v2x5blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:guide-dog" {...props}></Icon>
