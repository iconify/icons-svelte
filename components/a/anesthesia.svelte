<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfuwwhbkc.css';
import '../../css/c/c82mu65xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="lfuwwhbkc"/><path class="c82mu65xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:anesthesia" {...props}></Icon>
