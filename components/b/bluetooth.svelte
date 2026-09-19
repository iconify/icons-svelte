<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4nbh2ges.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4nbh2ges"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:bluetooth" {...props}></Icon>
