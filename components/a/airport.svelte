<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1kipxb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u1kipxb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:airport" {...props}></Icon>
