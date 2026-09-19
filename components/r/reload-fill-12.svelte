<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht2k5ha8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ht2k5ha8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:reload-fill-12" {...props}></Icon>
