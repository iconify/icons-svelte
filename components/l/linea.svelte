<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd_0f8xzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd_0f8xzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:linea" {...props}></Icon>
