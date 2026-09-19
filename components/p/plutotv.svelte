<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4c6_3buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4c6_3buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:plutotv" {...props}></Icon>
