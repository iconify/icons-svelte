<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmj2tv-_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lmj2tv-_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-cross-square-small" {...props}></Icon>
