<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amw_g50ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="amw_g50ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:comment-compact" {...props}></Icon>
