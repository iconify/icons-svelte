<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leyai0bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="leyai0bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hamburger-button" {...props}></Icon>
