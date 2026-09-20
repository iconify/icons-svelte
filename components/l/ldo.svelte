<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_yzt2k0i.css';
import '../../css/b/b_9exq3et.css';
import '../../css/a/aagrbllbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_yzt2k0i"/><path class="b_9exq3et"/><path class="aagrbllbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ldo" {...props}></Icon>
