<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wntykgjde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wntykgjde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:list-ol" {...props}></Icon>
