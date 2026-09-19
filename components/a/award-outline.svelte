<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfco4ib6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfco4ib6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:award-outline" {...props}></Icon>
