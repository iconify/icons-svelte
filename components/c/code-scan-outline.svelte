<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_1rmspdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_1rmspdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-scan-outline" {...props}></Icon>
