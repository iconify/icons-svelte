<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y73relbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y73relbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gramps-dark" {...props}></Icon>
