<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouuz4eb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ouuz4eb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:anchor" {...props}></Icon>
