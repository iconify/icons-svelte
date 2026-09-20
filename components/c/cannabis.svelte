<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odstembkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odstembkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cannabis" {...props}></Icon>
