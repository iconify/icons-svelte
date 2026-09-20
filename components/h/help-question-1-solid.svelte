<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpfo9nslk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mpfo9nslk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:help-question-1-solid" {...props}></Icon>
