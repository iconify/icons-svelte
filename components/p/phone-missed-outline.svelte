<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j12mt-oug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j12mt-oug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-missed-outline" {...props}></Icon>
