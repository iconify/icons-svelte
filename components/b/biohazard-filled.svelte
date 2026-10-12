<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2l34ybtf.css';
import '../../css/j/j8cdfd2tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2l34ybtf"/><path class="j8cdfd2tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:biohazard-filled" {...props}></Icon>
