<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb2z7spts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb2z7spts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:captioning-outline" {...props}></Icon>
