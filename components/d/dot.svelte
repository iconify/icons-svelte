<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k79efq2-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k79efq2-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dot" {...props}></Icon>
