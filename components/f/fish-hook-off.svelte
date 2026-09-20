<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tku4xni9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tku4xni9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fish-hook-off" {...props}></Icon>
