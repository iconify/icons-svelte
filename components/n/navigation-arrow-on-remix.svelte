<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq2q0_lyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gq2q0_lyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:navigation-arrow-on-remix" {...props}></Icon>
