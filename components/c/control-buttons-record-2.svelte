<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p84qtbaaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p84qtbaaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-record-2" {...props}></Icon>
