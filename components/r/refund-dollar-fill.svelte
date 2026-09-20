<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu1amlj5r.css';
import '../../css/m/mn6i_fowy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu1amlj5r"/><path class="mn6i_fowy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refund-dollar-fill" {...props}></Icon>
