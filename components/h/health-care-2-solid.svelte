<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmrdt7tkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jmrdt7tkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:health-care-2-solid" {...props}></Icon>
