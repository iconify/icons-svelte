<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay4i13k_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay4i13k_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:keyboard-bold" {...props}></Icon>
