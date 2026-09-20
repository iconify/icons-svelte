<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3gyipbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m3gyipbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-and-question-mark" {...props}></Icon>
