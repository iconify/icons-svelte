<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvlfp99rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvlfp99rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dna-fill" {...props}></Icon>
