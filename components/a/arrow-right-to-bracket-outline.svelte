<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unt4o16uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unt4o16uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrow-right-to-bracket-outline" {...props}></Icon>
