<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2fids0_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2fids0_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:plus" {...props}></Icon>
