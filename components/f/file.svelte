<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3p7xnusk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":597,"height":717};
const content = `<path class="v3p7xnusk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:file" {...props}></Icon>
