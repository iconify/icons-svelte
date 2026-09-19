<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1-kqhbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="d1-kqhbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bookmark-fill-12" {...props}></Icon>
