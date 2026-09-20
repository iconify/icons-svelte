<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eluck1b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eluck1b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:litlyx-light" {...props}></Icon>
