<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsczfvz-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rsczfvz-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:nurse-assistant-emergency" {...props}></Icon>
