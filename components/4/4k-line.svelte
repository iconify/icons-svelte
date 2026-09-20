<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1dz7wbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1dz7wbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:4k-line" {...props}></Icon>
