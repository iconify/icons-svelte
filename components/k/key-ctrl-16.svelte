<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an1_8sz0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="an1_8sz0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:key-ctrl-16" {...props}></Icon>
