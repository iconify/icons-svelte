<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlx8kijip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nlx8kijip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bolt-16-solid" {...props}></Icon>
