<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlm-d1pfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="mlm-d1pfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:document-words" {...props}></Icon>
