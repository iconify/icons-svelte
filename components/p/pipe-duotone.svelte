<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx83zxlsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx83zxlsq primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pipe-duotone" {...props}></Icon>
