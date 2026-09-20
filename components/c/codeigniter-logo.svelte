<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-6pixb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-6pixb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:codeigniter-logo" {...props}></Icon>
