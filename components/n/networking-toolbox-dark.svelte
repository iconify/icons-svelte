<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j92q2kbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j92q2kbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:networking-toolbox-dark" {...props}></Icon>
