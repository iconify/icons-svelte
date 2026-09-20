<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0lgx_3bc.css';
import '../../css/d/dh1xuibar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="c0lgx_3bc"/><path clip-rule="evenodd" class="dh1xuibar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:outdent" {...props}></Icon>
