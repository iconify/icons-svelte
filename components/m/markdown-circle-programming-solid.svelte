<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzuk-mb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qzuk-mb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:markdown-circle-programming-solid" {...props}></Icon>
