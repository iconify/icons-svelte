<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_e70abvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_e70abvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:certificate-2-fill" {...props}></Icon>
