<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kob08kh-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kob08kh-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minecraft-light" {...props}></Icon>
