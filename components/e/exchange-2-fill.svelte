<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc8h3-brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc8h3-brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:exchange-2-fill" {...props}></Icon>
