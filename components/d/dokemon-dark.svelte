<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbftvacto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rbftvacto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dokemon-dark" {...props}></Icon>
