<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmc5rlb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cmc5rlb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-solid" {...props}></Icon>
