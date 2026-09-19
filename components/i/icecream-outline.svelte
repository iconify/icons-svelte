<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejutc9btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejutc9btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:icecream-outline" {...props}></Icon>
