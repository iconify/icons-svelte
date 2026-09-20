<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm5leryez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm5leryez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:de-longhi" {...props}></Icon>
