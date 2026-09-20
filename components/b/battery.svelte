<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk-k9mswx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk-k9mswx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:battery" {...props}></Icon>
