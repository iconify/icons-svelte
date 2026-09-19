<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg97db8xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg97db8xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-process-01" {...props}></Icon>
