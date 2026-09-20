<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrh9d6z6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrh9d6z6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-heart" {...props}></Icon>
