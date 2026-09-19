<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7nhbzsmz.css';
import '../../css/v/v3v551bqy.css';
import '../../css/j/j94t_ebkm.css';
import '../../css/x/xzxjqabgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="e7nhbzsmz"/><path class="v3v551bqy"/><path class="j94t_ebkm"/><path class="xzxjqabgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:file" {...props}></Icon>
