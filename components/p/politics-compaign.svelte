<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd8krycwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qd8krycwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:politics-compaign" {...props}></Icon>
