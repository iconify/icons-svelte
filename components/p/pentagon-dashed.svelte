<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdh3wsbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdh3wsbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pentagon-dashed" {...props}></Icon>
