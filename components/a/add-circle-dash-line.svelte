<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyk2onbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyk2onbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:add-circle-dash-line" {...props}></Icon>
