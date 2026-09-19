<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf603ubza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf603ubza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:champagne-glasses-outline" {...props}></Icon>
