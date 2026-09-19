<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpkbf0bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpkbf0bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bluetooth" {...props}></Icon>
