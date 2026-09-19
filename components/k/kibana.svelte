<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwr_9_bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xwr_9_bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:kibana" {...props}></Icon>
