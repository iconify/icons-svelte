<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm8mx7q9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm8mx7q9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-check-outline" {...props}></Icon>
