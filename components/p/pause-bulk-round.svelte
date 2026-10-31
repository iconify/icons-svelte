<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erehkzbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erehkzbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pause-bulk-round" {...props}></Icon>
