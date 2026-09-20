<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnfbg9tya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnfbg9tya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-cog-outline" {...props}></Icon>
