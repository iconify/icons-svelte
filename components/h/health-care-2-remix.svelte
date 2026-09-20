<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzysto7mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xzysto7mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:health-care-2-remix" {...props}></Icon>
