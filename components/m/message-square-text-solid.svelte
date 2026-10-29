<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wigpk_r0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wigpk_r0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-text-solid" {...props}></Icon>
