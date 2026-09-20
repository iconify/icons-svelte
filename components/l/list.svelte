<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj1i9xbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qj1i9xbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:list" {...props}></Icon>
