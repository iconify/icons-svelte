<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5tn3lm6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v5tn3lm6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-graph-duotone" {...props}></Icon>
