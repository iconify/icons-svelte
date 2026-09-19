<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtohnabyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtohnabyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrow-left-to-bracket-outline" {...props}></Icon>
