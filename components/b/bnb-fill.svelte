<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcj6_1b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcj6_1b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bnb-fill" {...props}></Icon>
