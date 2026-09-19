<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg7n252at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gg7n252at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:fist" {...props}></Icon>
