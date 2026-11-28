<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7o99qb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y7o99qb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:envelope-x-light" {...props}></Icon>
