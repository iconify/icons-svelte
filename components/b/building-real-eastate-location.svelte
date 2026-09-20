<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smwwurb-l.css';
import '../../css/r/r2bxk5btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="smwwurb-l"/><path class="r2bxk5btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:building-real-eastate-location" {...props}></Icon>
