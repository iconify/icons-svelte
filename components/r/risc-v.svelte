<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8o1-8brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j8o1-8brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:risc-v" {...props}></Icon>
