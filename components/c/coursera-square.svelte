<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxvmtd8dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xxvmtd8dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:coursera-square" {...props}></Icon>
