<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mneg3gbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mneg3gbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-collapse-2-line" {...props}></Icon>
