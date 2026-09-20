<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk7o3vb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk7o3vb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:focus-filled" {...props}></Icon>
