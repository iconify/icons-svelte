<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgpd84i-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tgpd84i-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:pass-filled-compact" {...props}></Icon>
