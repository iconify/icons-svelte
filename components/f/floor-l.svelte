<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/incm1-bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="incm1-bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floor-l" {...props}></Icon>
