<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa-nw0wun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa-nw0wun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-return-outline" {...props}></Icon>
