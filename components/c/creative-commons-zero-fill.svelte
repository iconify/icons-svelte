<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3te10bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3te10bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:creative-commons-zero-fill" {...props}></Icon>
