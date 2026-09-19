<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kygawes_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="kygawes_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-prescription" {...props}></Icon>
