<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhw393bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhw393bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:meetup" {...props}></Icon>
