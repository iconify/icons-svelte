<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idltwcbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="idltwcbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-helmet-riding-atv" {...props}></Icon>
