<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnuozhkls.css';
import '../../css/s/s1i3vlbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="bnuozhkls"/><path class="s1i3vlbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:data-checked-filled" {...props}></Icon>
