<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xioo67b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xioo67b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:receipt-euro-filled" {...props}></Icon>
