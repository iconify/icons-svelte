<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epi4yab0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="epi4yab0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:firebase" {...props}></Icon>
