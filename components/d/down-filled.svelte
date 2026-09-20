<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz_cz4bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sz_cz4bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:down-filled" {...props}></Icon>
