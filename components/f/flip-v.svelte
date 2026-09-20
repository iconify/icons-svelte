<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhv8k2asq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhv8k2asq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:flip-v" {...props}></Icon>
