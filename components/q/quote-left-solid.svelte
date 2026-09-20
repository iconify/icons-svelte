<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b450yybgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b450yybgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:quote-left-solid" {...props}></Icon>
