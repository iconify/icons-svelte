<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz_kf-bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz_kf-bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:liver" {...props}></Icon>
