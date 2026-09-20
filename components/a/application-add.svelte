<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sph3r42wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sph3r42wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:application-add" {...props}></Icon>
