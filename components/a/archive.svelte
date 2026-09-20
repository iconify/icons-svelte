<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea2px6x9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ea2px6x9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:archive" {...props}></Icon>
