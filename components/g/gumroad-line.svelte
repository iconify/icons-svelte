<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pytlbv_yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pytlbv_yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gumroad-line" {...props}></Icon>
