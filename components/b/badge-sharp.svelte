<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxv8z0-zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxv8z0-zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-sharp" {...props}></Icon>
