<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5780hbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i5780hbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:button-record-3-flat" {...props}></Icon>
