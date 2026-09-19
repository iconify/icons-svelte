<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2pau0bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="w2pau0bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:camera" {...props}></Icon>
