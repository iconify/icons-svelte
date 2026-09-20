<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivkodgbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivkodgbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-right-bottom-left" {...props}></Icon>
