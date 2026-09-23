<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq5v0fbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gq5v0fbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pgsty-silo-light" {...props}></Icon>
