<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mla3oqfvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mla3oqfvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:fan" {...props}></Icon>
