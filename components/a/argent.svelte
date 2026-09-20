<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmablib0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmablib0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:argent" {...props}></Icon>
