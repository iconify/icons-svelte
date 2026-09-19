<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-7_1mb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k-7_1mb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:funnel-solid" {...props}></Icon>
