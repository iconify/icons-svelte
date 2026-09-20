<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g02lxkxig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g02lxkxig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circle-outline-with-dot-outline" {...props}></Icon>
