<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fom46j_ot.css';
import '../../css/e/en5_3bbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fom46j_ot"/><path class="en5_3bbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mentioned-filled" {...props}></Icon>
