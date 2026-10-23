<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc3rm7mko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc3rm7mko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:navigation" {...props}></Icon>
