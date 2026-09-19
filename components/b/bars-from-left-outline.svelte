<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq04mtb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq04mtb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bars-from-left-outline" {...props}></Icon>
