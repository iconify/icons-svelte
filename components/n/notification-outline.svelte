<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6xl-g2-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6xl-g2-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:notification-outline" {...props}></Icon>
