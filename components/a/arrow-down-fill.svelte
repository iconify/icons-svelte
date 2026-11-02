<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj_3tub_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj_3tub_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-fill" {...props}></Icon>
