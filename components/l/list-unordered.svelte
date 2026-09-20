<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3nx7ozsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3nx7ozsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:list-unordered" {...props}></Icon>
