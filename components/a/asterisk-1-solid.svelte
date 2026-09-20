<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ovjw7gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d2ovjw7gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:asterisk-1-solid" {...props}></Icon>
