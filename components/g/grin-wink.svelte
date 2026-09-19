<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia_eumbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="ia_eumbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grin-wink" {...props}></Icon>
