<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou56esbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou56esbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-download-line" {...props}></Icon>
