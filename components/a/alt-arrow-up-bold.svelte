<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsbsd2blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsbsd2blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-up-bold" {...props}></Icon>
