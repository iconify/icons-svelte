<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr5jz9f4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr5jz9f4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-moon" {...props}></Icon>
