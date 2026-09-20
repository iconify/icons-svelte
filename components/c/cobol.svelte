<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6f5j_qip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="z6f5j_qip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cobol" {...props}></Icon>
