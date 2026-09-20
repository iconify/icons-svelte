<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8symv77j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="w8symv77j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:post-excerpt" {...props}></Icon>
