<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooyaa4bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ooyaa4bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:anchor" {...props}></Icon>
