<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvl374bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvl374bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:binary-sharp" {...props}></Icon>
