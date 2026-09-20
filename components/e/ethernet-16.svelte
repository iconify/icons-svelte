<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bliib4s-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bliib4s-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ethernet-16" {...props}></Icon>
