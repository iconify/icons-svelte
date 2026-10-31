<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9fzqgnrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9fzqgnrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ambulance-gloss" {...props}></Icon>
