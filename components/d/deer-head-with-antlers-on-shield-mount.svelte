<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_imxmbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b_imxmbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:deer-head-with-antlers-on-shield-mount" {...props}></Icon>
