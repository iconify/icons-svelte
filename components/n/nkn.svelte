<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_zgehb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_zgehb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nkn" {...props}></Icon>
