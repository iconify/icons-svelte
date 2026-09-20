<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfcjx_esq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfcjx_esq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-off" {...props}></Icon>
