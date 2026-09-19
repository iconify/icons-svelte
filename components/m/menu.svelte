<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vokcyn7-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vokcyn7-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:menu" {...props}></Icon>
