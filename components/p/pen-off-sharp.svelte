<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjew7nbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjew7nbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pen-off-sharp" {...props}></Icon>
