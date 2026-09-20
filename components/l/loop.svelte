<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k07c9wb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k07c9wb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:loop" {...props}></Icon>
