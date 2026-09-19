<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e29ch1r5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e29ch1r5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cloud-download" {...props}></Icon>
