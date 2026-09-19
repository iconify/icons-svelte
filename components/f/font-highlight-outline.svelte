<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dauqcps4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dauqcps4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:font-highlight-outline" {...props}></Icon>
