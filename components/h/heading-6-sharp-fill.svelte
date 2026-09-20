<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf_h8hs5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_h8hs5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-6-sharp-fill" {...props}></Icon>
