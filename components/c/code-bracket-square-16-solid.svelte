<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldhnb-but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ldhnb-but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:code-bracket-square-16-solid" {...props}></Icon>
