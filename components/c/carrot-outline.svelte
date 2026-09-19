<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soz38ybee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soz38ybee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:carrot-outline" {...props}></Icon>
