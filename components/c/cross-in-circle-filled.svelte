<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x58rzoi6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x58rzoi6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:cross-in-circle-filled" {...props}></Icon>
