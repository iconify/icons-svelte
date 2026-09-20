<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwxksm_9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwxksm_9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-left-bold-outline" {...props}></Icon>
