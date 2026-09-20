<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gii_burqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gii_burqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:capnp" {...props}></Icon>
