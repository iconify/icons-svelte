<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dia0nqdkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dia0nqdkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:keyboard" {...props}></Icon>
