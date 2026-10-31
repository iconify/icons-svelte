<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvw8pmbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvw8pmbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fish-gloss" {...props}></Icon>
