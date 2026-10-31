<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1rmxw4ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1rmxw4ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-1-fill-round" {...props}></Icon>
