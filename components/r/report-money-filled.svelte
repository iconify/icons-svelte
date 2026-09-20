<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3s8xnb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3s8xnb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:report-money-filled" {...props}></Icon>
