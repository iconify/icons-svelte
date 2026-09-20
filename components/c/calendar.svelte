<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnmhc85yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnmhc85yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar" {...props}></Icon>
