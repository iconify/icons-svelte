<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dndzo0oqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dndzo0oqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:onestream" {...props}></Icon>
