<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugjmlib4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugjmlib4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-clock-fill" {...props}></Icon>
