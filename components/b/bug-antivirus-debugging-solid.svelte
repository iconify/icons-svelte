<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esf1olrah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="esf1olrah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-antivirus-debugging-solid" {...props}></Icon>
