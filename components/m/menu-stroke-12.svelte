<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noljisb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="noljisb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:menu-stroke-12" {...props}></Icon>
