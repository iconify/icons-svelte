<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_e0-5e6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_e0-5e6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-end-horizontal" {...props}></Icon>
