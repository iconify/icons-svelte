<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzk5mpk7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nzk5mpk7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:attach-compact" {...props}></Icon>
