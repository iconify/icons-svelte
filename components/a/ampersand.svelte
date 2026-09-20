<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka83c5b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka83c5b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:ampersand" {...props}></Icon>
