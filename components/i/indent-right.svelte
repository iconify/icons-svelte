<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq19trb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uq19trb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:indent-right" {...props}></Icon>
