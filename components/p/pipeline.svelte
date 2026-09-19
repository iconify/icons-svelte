<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfouhbcny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfouhbcny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:pipeline" {...props}></Icon>
