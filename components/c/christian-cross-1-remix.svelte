<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz8scw1xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sz8scw1xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:christian-cross-1-remix" {...props}></Icon>
