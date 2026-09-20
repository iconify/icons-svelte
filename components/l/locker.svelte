<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hob_kaboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hob_kaboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:locker" {...props}></Icon>
