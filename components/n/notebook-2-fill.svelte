<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw5_q-bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw5_q-bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notebook-2-fill" {...props}></Icon>
