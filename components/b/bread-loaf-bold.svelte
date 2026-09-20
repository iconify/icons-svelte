<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb7he3brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb7he3brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bread-loaf-bold" {...props}></Icon>
