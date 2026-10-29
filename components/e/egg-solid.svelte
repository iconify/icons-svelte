<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib37v-b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib37v-b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:egg-solid" {...props}></Icon>
