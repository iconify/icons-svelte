<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghfixm1dc.css';
import '../../css/q/qii6rvmzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghfixm1dc"/><path class="qii6rvmzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copyright-bold-duotone" {...props}></Icon>
