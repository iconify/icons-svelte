<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-1v2wi4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1v2wi4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grid-2x2-plus" {...props}></Icon>
