<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_vzqpjha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_vzqpjha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-signal-bold" {...props}></Icon>
