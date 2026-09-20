<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0oo4lbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z0oo4lbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:invoice-outline" {...props}></Icon>
