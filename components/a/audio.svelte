<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u66vm_5px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u66vm_5px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:audio" {...props}></Icon>
