<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zecugyy5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zecugyy5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-2-broken" {...props}></Icon>
