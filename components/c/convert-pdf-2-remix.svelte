<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyba1rbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kyba1rbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:convert-pdf-2-remix" {...props}></Icon>
