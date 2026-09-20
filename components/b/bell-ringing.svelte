<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba3_y3ujc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba3_y3ujc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-ringing" {...props}></Icon>
