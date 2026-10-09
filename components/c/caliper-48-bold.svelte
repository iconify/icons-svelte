<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm2leab2g.css';
import '../../css/y/yg7y-7bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pm2leab2g"/><path class="yg7y-7bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caliper-48-bold" {...props}></Icon>
