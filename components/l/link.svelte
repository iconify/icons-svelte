<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt7noobxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zt7noobxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:link" {...props}></Icon>
