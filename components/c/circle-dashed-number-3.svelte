<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e67bpz24e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e67bpz24e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-number-3" {...props}></Icon>
