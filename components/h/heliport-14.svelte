<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-3d54bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a-3d54bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:heliport-14" {...props}></Icon>
