<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-m9inbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d-m9inbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:pet-animals-bear" {...props}></Icon>
