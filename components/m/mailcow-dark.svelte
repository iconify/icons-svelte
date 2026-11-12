<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha0-h7bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ha0-h7bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailcow-dark" {...props}></Icon>
