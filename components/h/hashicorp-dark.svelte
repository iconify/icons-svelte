<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwgdm_brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qwgdm_brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-dark" {...props}></Icon>
