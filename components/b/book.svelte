<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/botcjxbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="botcjxbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:book" {...props}></Icon>
