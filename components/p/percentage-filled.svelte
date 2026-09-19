<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtddmc8gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mtddmc8gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:percentage-filled" {...props}></Icon>
