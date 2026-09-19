<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3w0cnbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="g3w0cnbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cube-box-fill" {...props}></Icon>
