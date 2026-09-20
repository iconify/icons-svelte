<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hme_mebaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hme_mebaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:microphone-cancelled" {...props}></Icon>
