<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwb06vbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":484,"height":512};
const content = `<path class="st1 xwb06vbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:conversation" {...props}></Icon>
