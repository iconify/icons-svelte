<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3odewufb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h3odewufb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-new-filled" {...props}></Icon>
