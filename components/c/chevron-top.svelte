<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqgyk5b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fqgyk5b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-top" {...props}></Icon>
