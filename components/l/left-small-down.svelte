<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb9vr8bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sb9vr8bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:left-small-down" {...props}></Icon>
