<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxfnjdc7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxfnjdc7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-diagram" {...props}></Icon>
