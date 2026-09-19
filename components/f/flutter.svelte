<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8kaj0xhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":512};
const content = `<path class="h8kaj0xhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:flutter" {...props}></Icon>
