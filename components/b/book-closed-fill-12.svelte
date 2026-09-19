<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5ur80tmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v5ur80tmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-closed-fill-12" {...props}></Icon>
