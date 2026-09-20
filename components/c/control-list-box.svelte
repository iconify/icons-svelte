<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8sj5ne3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="e8sj5ne3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:control-list-box" {...props}></Icon>
