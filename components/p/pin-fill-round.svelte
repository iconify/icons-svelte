<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x50hxtswz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x50hxtswz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pin-fill-round" {...props}></Icon>
