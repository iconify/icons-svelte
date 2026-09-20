<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xahm4zbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xahm4zbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-moon-sharp" {...props}></Icon>
