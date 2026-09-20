<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7qcs1agw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7qcs1agw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:pixelarticons" {...props}></Icon>
