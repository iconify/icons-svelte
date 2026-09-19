<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0auchbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0auchbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:jpg-01" {...props}></Icon>
