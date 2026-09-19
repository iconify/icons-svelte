<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfz61wbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfz61wbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:circle-pause-outline" {...props}></Icon>
