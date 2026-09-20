<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo2007t4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uo2007t4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-virus-document-remix" {...props}></Icon>
