<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozzkksb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozzkksb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:language-outline" {...props}></Icon>
