<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld3pukxpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld3pukxpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:papper-plane-outline" {...props}></Icon>
