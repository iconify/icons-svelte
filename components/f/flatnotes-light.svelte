<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf32sibdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gf32sibdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flatnotes-light" {...props}></Icon>
