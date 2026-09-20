<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwhz73bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwhz73bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-s-box-outline" {...props}></Icon>
