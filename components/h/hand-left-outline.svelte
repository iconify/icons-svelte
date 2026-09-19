<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c13bt8b3z.css';
import '../../css/l/lgvvujlva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c13bt8b3z"/><path class="lgvvujlva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:hand-left-outline" {...props}></Icon>
