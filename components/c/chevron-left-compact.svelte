<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd53c6jcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hd53c6jcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chevron-left-compact" {...props}></Icon>
