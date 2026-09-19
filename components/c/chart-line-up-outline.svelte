<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubj1bvaep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubj1bvaep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chart-line-up-outline" {...props}></Icon>
