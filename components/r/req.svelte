<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5xt8ebyb.css';
import '../../css/y/yls_sbcyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5xt8ebyb"/><path class="yls_sbcyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:req" {...props}></Icon>
