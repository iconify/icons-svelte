<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elucaybxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elucaybxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freepbx-light" {...props}></Icon>
