<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iif_9hzvg.css';
import '../../css/k/klfo1ab7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iif_9hzvg"/><path class="klfo1ab7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:enterprise" {...props}></Icon>
