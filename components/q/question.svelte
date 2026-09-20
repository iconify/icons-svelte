<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efp6idufy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="efp6idufy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:question" {...props}></Icon>
