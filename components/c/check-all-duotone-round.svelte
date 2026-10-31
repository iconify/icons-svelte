<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9910ubpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9910ubpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:check-all-duotone-round" {...props}></Icon>
