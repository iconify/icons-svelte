<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h524gymsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h524gymsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loader-4-line" {...props}></Icon>
