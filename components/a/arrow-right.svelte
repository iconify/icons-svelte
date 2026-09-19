<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgx_e8bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgx_e8bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:arrow-right" {...props}></Icon>
