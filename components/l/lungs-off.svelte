<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivg15v0kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivg15v0kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lungs-off" {...props}></Icon>
