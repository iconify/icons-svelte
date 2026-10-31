<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avn7179zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avn7179zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:parasol-round" {...props}></Icon>
