<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx1k52b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="nx1k52b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:heading-level-3" {...props}></Icon>
