<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf57mkbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kf57mkbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:folder-opened-compact" {...props}></Icon>
