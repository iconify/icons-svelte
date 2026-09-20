<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh-2zhm_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh-2zhm_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-l" {...props}></Icon>
