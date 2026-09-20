<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gena9bc0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gena9bc0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bag-outline" {...props}></Icon>
