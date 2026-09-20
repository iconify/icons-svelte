<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt9qsmbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nt9qsmbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-stop-2" {...props}></Icon>
