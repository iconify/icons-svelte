<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3tiwg6bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3tiwg6bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:forward-outline" {...props}></Icon>
