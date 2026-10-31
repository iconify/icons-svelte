<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njr581lvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njr581lvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:log-in-round" {...props}></Icon>
