<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhzzqd1cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhzzqd1cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fork-filled" {...props}></Icon>
