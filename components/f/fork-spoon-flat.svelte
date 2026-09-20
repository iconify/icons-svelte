<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ias7glzgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ias7glzgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:fork-spoon-flat" {...props}></Icon>
