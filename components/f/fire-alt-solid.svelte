<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pez3-pb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pez3-pb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fire-alt-solid" {...props}></Icon>
