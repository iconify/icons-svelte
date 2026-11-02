<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duhpuebnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duhpuebnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-square-30-fill" {...props}></Icon>
