<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl7o9-bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl7o9-bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-wink" {...props}></Icon>
