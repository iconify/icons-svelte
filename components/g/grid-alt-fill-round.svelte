<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj14bacvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj14bacvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:grid-alt-fill-round" {...props}></Icon>
