<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hze5yvdeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hze5yvdeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:potted-plant-gloss" {...props}></Icon>
