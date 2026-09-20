<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehpyr2bhb.css';
import '../../css/d/d0za96bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehpyr2bhb"/><path class="d0za96bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:oath" {...props}></Icon>
