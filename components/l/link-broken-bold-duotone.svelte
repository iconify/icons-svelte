<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvj8odlbj.css';
import '../../css/i/iw1lz7bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvj8odlbj"/><path class="iw1lz7bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-broken-bold-duotone" {...props}></Icon>
