<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0r_64bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a0r_64bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hurricane" {...props}></Icon>
