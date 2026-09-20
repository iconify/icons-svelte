<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vecwkqnkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vecwkqnkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flashlight-off" {...props}></Icon>
