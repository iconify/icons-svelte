<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxrpz4blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="jxrpz4blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-medical-alt" {...props}></Icon>
