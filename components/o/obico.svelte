<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta4qt8blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ta4qt8blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obico" {...props}></Icon>
