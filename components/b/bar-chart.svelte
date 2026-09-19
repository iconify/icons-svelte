<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2v1khb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2v1khb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bar-chart" {...props}></Icon>
