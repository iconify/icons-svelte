<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfamr8bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfamr8bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fingerprint" {...props}></Icon>
