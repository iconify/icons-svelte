<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr2tp2u2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr2tp2u2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:rocket" {...props}></Icon>
