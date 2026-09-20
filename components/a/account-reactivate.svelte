<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn_-277ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn_-277ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-reactivate" {...props}></Icon>
