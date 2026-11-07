<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7y0uxbsp.css';
import '../../css/l/l1ebf737s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7y0uxbsp"/><path clip-rule="evenodd" class="l1ebf737s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cpu-bold" {...props}></Icon>
