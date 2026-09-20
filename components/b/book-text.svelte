<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlhcq27sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlhcq27sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:book-text" {...props}></Icon>
