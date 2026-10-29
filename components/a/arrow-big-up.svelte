<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgy0btxid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgy0btxid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-big-up" {...props}></Icon>
