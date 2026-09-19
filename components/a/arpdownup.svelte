<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syygxic3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="syygxic3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:arpdownup" {...props}></Icon>
