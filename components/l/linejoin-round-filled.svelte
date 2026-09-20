<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-9x3bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kb-9x3bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:linejoin-round-filled" {...props}></Icon>
