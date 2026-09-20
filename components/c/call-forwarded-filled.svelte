<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7q3yfbdi.css';
import '../../css/p/p9omok_2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7q3yfbdi"/><path class="p9omok_2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:call-forwarded-filled" {...props}></Icon>
