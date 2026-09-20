<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tucqnsujk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tucqnsujk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:quotation-2" {...props}></Icon>
