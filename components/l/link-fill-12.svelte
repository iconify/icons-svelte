<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv_wzebzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gv_wzebzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:link-fill-12" {...props}></Icon>
