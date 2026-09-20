<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnj5y5did.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnj5y5did"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hackaday" {...props}></Icon>
