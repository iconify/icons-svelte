<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjf-xsbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xjf-xsbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jetpackcompose-wordmark" {...props}></Icon>
