<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvhlhhovd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tvhlhhovd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:image-saturation-vertical-remix" {...props}></Icon>
