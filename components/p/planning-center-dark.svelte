<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_lmkqbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_lmkqbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-dark" {...props}></Icon>
