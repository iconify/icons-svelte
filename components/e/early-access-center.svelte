<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0p-5_bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0p-5_bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:early-access-center" {...props}></Icon>
