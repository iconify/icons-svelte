<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck0-ziw1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck0-ziw1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cat" {...props}></Icon>
