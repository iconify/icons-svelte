<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs5aucclh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs5aucclh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:caret-left-outline" {...props}></Icon>
