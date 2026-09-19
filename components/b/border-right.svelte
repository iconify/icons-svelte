<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l37hiob-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l37hiob-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-right" {...props}></Icon>
