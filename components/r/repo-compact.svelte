<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qep29e6oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qep29e6oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:repo-compact" {...props}></Icon>
