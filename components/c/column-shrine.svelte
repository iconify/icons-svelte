<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs3vqsb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qs3vqsb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:column-shrine" {...props}></Icon>
