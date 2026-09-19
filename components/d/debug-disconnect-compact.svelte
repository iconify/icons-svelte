<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1zalobua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="z1zalobua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-disconnect-compact" {...props}></Icon>
