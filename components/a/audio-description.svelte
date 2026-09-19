<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2b9z8qre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="l2b9z8qre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:audio-description" {...props}></Icon>
