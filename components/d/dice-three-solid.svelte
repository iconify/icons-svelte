<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr1ljxbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sr1ljxbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dice-three-solid" {...props}></Icon>
