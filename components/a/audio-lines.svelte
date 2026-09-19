<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xilkr0bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xilkr0bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:audio-lines" {...props}></Icon>
