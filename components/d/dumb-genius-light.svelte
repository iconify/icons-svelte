<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hej2h2wme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hej2h2wme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumb-genius-light" {...props}></Icon>
