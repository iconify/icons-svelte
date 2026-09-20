<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj7pex86r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hj7pex86r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:pet-animals-pig" {...props}></Icon>
