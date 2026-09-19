<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jclt3ehgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jclt3ehgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:filter-dollar-outline" {...props}></Icon>
