<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-7ky8bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="s-7ky8bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:resize-corner-ne" {...props}></Icon>
