<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqhoic-6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqhoic-6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:inbox-full" {...props}></Icon>
