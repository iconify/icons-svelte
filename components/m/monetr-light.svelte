<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oycn88bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oycn88bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:monetr-light" {...props}></Icon>
