<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6xiyt8wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i6xiyt8wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:remote-compact" {...props}></Icon>
