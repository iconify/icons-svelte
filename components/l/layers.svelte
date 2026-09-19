<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p43yp_3ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p43yp_3ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:layers" {...props}></Icon>
