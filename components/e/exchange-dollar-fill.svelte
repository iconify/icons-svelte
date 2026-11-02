<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sif1ckb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sif1ckb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-dollar-fill" {...props}></Icon>
