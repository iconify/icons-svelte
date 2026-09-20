<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbdn16phg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qbdn16phg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dashboard-circle-remix" {...props}></Icon>
