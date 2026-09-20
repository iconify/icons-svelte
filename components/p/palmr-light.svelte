<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhq-3hb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fhq-3hb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:palmr-light" {...props}></Icon>
