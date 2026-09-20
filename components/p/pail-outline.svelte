<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtb2k4dkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtb2k4dkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pail-outline" {...props}></Icon>
