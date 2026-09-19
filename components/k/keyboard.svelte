<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-b0jlzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="tc-b0jlzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:keyboard" {...props}></Icon>
