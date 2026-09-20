<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m93qdybrp.css';
import '../../css/y/yu8tkqs3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="m93qdybrp"/><path class="yu8tkqs3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:medium-skin-tone" {...props}></Icon>
