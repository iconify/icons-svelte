<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg1279bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1279bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:graduation-cap-gloss" {...props}></Icon>
