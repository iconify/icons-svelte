<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf61a3ufc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf61a3ufc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-share" {...props}></Icon>
