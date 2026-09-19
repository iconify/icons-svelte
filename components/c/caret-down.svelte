<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly4ps1k1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ly4ps1k1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:caret-down" {...props}></Icon>
