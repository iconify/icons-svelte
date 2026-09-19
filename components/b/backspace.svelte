<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j73vikbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j73vikbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:backspace" {...props}></Icon>
