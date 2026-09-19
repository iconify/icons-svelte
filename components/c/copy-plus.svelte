<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfgw7gb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zfgw7gb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:copy-plus" {...props}></Icon>
