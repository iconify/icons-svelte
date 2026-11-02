<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bymq2-bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bymq2-bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-window-line" {...props}></Icon>
