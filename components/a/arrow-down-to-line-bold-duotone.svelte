<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omll7putu.css';
import '../../css/b/bidhrk63b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omll7putu"/><path class="bidhrk63b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-down-to-line-bold-duotone" {...props}></Icon>
