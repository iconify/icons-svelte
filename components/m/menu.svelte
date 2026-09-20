<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kinw1xbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kinw1xbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:menu" {...props}></Icon>
