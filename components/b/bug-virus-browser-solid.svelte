<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opgs6bbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="opgs6bbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-virus-browser-solid" {...props}></Icon>
