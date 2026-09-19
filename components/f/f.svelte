<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3z343zim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="u3z343zim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:f" {...props}></Icon>
