<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3oa-6rxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3oa-6rxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-plus-line" {...props}></Icon>
