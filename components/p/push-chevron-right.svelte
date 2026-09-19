<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm2phzf1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm2phzf1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:push-chevron-right" {...props}></Icon>
