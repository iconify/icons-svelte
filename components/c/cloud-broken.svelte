<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp93toeom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp93toeom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-broken" {...props}></Icon>
