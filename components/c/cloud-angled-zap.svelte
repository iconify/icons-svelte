<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu_bbh2lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu_bbh2lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-angled-zap" {...props}></Icon>
