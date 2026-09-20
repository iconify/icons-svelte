<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4rx783-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4rx783-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:image-broken" {...props}></Icon>
