<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyguhx2tf.css';
import '../../css/z/zme4g8b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cyguhx2tf"/><path class="zme4g8b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-vpn-for-vpc" {...props}></Icon>
