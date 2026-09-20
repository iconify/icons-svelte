<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz7uw_vip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz7uw_vip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:comment" {...props}></Icon>
