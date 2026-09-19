<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1-czjb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1-czjb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cake-slice-filled" {...props}></Icon>
