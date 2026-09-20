<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no0_jw34d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="no0_jw34d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rotate-locked-filled" {...props}></Icon>
