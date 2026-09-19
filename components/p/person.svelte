<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4g3ob5-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="c4g3ob5-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:person" {...props}></Icon>
