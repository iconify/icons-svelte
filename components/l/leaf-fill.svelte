<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr00z-buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr00z-buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:leaf-fill" {...props}></Icon>
