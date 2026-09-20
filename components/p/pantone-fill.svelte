<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytcf_hsmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytcf_hsmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pantone-fill" {...props}></Icon>
