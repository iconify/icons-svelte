<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td4xcbcaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td4xcbcaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:palette-fill-round" {...props}></Icon>
