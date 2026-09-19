<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzedyzb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzedyzb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:file" {...props}></Icon>
