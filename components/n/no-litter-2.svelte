<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpva-4bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpva-4bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-litter-2" {...props}></Icon>
