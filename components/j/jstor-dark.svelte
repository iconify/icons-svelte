<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br3r0diof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="br3r0diof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jstor-dark" {...props}></Icon>
