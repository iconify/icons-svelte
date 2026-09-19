<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4mh9zb-o.css';
import '../../css/b/bpl1kribr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c4mh9zb-o"/><path class="bpl1kribr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:coreui-c" {...props}></Icon>
