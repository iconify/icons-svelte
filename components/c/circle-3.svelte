<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lncx4q9ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lncx4q9ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:circle-3" {...props}></Icon>
