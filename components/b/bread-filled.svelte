<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-grs3ykq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-grs3ykq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bread-filled" {...props}></Icon>
