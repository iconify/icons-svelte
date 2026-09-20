<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p03e-lbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p03e-lbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-up-small-outline" {...props}></Icon>
