<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew902cm0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew902cm0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:laptop-file-outline" {...props}></Icon>
