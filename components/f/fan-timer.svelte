<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqs_sjbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqs_sjbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fan-timer" {...props}></Icon>
