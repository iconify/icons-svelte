<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_2-9c3fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s_2-9c3fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-aa" {...props}></Icon>
