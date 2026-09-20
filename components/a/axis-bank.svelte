<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb_6qrbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb_6qrbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:axis-bank" {...props}></Icon>
