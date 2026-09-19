<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvpnn-2xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="dvpnn-2xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:round" {...props}></Icon>
