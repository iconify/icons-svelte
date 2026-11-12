<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooy89kzvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ooy89kzvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:i-librarian" {...props}></Icon>
