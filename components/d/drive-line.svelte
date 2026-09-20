<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn3fnbnbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn3fnbnbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drive-line" {...props}></Icon>
