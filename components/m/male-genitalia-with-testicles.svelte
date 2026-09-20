<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6qxiac-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z6qxiac-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:male-genitalia-with-testicles" {...props}></Icon>
