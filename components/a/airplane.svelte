<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu0undb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qu0undb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:airplane" {...props}></Icon>
