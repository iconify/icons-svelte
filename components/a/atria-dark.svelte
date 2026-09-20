<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2x7se42l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y2x7se42l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atria-dark" {...props}></Icon>
