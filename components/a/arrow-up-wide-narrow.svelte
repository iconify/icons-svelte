<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tke0wbcic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tke0wbcic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-up-wide-narrow" {...props}></Icon>
