<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1a2x8b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1a2x8b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:replace-filled" {...props}></Icon>
