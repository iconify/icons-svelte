<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9pf8_h-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9pf8_h-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-takeoff-fill-round" {...props}></Icon>
