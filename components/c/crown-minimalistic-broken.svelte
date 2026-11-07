<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yphyl1bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yphyl1bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-minimalistic-broken" {...props}></Icon>
