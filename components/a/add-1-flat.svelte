<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs903ixzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gs903ixzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:add-1-flat" {...props}></Icon>
