<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg9qaby-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="qg9qaby-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-medical" {...props}></Icon>
