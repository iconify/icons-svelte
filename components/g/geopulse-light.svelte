<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdiorvbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fdiorvbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:geopulse-light" {...props}></Icon>
