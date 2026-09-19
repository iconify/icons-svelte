<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju8hpn7kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju8hpn7kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:pen-outline" {...props}></Icon>
