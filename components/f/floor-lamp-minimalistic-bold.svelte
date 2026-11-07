<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhocsxiwx.css';
import '../../css/h/hlr7qvbgb.css';
import '../../css/y/y1m3u927f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhocsxiwx"/><path class="hlr7qvbgb"/><path class="y1m3u927f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:floor-lamp-minimalistic-bold" {...props}></Icon>
