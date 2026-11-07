<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl66i7bqg.css';
import '../../css/n/n8rwppsqt.css';
import '../../css/w/wrft_xvmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="n8rwppsqt"/><path class="wrft_xvmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-slash-bold-duotone" {...props}></Icon>
