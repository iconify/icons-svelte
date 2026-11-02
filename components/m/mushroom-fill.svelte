<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc16_k8sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc16_k8sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mushroom-fill" {...props}></Icon>
