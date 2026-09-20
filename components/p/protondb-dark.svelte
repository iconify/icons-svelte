<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8ql71r8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y8ql71r8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:protondb-dark" {...props}></Icon>
