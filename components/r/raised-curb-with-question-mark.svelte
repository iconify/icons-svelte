<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sceiphbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sceiphbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:raised-curb-with-question-mark" {...props}></Icon>
