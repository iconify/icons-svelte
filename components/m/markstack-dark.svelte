<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdhfqclbu.css';
import '../../css/r/rh-ehybjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdhfqclbu"/><path class="rh-ehybjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:markstack-dark" {...props}></Icon>
