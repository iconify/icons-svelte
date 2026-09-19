<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q89-ixbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q89-ixbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:label" {...props}></Icon>
