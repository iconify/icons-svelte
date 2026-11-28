<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao__mmbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao__mmbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-loop-limit" {...props}></Icon>
