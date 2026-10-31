<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf0yc8b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf0yc8b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-plus-gloss" {...props}></Icon>
