<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxb3bvbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mxb3bvbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-shrink-1-expand-retract-shrink-bigger-big-small-smaller" {...props}></Icon>
