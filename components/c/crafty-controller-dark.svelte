<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0f-q8b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0f-q8b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crafty-controller-dark" {...props}></Icon>
