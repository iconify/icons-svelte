<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqlzyghhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqlzyghhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pound-sterling-sharp-duotone" {...props}></Icon>
