<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqn26fp0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqn26fp0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:add-circle-fill" {...props}></Icon>
