<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnhnnwbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bnhnnwbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-right-fill-12" {...props}></Icon>
