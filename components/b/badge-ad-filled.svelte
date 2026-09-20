<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evmgakbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evmgakbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-ad-filled" {...props}></Icon>
