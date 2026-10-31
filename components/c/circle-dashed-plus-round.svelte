<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax1xbl3ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax1xbl3ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-plus-round" {...props}></Icon>
