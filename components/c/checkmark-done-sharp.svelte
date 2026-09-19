<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0al1cbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0al1cbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:checkmark-done-sharp" {...props}></Icon>
