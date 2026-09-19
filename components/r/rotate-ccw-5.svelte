<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bazxsibde.css';
import '../../css/e/eselt7ksv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bazxsibde"/><path class="eselt7ksv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rotate-ccw-5" {...props}></Icon>
