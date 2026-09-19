<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqrk28aif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqrk28aif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:magnet" {...props}></Icon>
