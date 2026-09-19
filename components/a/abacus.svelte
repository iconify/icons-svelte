<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3f-3twlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l3f-3twlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:abacus" {...props}></Icon>
