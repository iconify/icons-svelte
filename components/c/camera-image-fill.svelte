<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jew4uiv9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jew4uiv9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:camera-image-fill" {...props}></Icon>
