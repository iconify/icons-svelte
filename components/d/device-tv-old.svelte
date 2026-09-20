<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqgb_dwuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqgb_dwuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-tv-old" {...props}></Icon>
