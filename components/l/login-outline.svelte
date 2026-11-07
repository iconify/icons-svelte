<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfi9t8bxj.css';
import '../../css/z/zw-inltah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfi9t8bxj"/><path class="zw-inltah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-outline" {...props}></Icon>
