<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sslbt3clz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sslbt3clz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:columns-two-halfs" {...props}></Icon>
