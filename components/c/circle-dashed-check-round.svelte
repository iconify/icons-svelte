<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4h-lfodh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4h-lfodh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-check-round" {...props}></Icon>
