<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zajftkb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zajftkb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:asterisk-1" {...props}></Icon>
