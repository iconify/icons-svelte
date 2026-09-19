<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0vude17c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0vude17c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:computer-speaker-outline" {...props}></Icon>
