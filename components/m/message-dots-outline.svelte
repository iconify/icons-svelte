<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a98b60bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a98b60bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:message-dots-outline" {...props}></Icon>
