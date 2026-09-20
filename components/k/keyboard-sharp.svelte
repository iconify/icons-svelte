<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhtx9-b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhtx9-b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:keyboard-sharp" {...props}></Icon>
