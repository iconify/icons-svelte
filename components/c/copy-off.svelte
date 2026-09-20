<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7krgy5kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7krgy5kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:copy-off" {...props}></Icon>
