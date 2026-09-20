<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf6g9sb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf6g9sb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-bulleted-settings-outline" {...props}></Icon>
