<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwiw72nap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwiw72nap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-n100" {...props}></Icon>
