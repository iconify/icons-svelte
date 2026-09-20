<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbtcsxbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbtcsxbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rocket-launch-outline" {...props}></Icon>
