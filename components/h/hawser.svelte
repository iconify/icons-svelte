<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adpj7nbwk.css';
import '../../css/w/wp44u6bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="adpj7nbwk"/><path class="wp44u6bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hawser" {...props}></Icon>
