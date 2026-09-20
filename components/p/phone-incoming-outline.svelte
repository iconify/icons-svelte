<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvs494b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvs494b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-incoming-outline" {...props}></Icon>
