<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6p-le5ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6p-le5ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ampersand" {...props}></Icon>
