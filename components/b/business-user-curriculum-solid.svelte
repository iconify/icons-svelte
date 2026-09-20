<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_oqk_xza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i_oqk_xza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:business-user-curriculum-solid" {...props}></Icon>
