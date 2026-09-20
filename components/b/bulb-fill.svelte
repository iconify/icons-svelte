<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf-_avbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jf-_avbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bulb-fill" {...props}></Icon>
