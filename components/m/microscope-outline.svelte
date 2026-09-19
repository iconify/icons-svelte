<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aok5afb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aok5afb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:microscope-outline" {...props}></Icon>
