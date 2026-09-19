<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qokuvh32r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qokuvh32r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:edit-04" {...props}></Icon>
