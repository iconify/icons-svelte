<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6r8n0old.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z6r8n0old"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-square-fill" {...props}></Icon>
