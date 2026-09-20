<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm1r5-bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zm1r5-bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bar-code-filled" {...props}></Icon>
