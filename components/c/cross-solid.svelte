<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mly2-fb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mly2-fb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cross-solid" {...props}></Icon>
