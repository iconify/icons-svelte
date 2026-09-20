<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk8svwb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gk8svwb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-outline" {...props}></Icon>
