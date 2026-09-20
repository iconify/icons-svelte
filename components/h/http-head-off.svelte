<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3spu_4jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3spu_4jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-head-off" {...props}></Icon>
