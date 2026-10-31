<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9p7p2o5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9p7p2o5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-stop-fill-round" {...props}></Icon>
