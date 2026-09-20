<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6ci_ccqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6ci_ccqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:link-fill" {...props}></Icon>
