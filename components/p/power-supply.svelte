<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vytblz0vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vytblz0vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:power-supply" {...props}></Icon>
