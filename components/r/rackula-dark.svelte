<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chbs9jbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="chbs9jbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rackula-dark" {...props}></Icon>
