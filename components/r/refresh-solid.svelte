<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp8m3bbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp8m3bbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:refresh-solid" {...props}></Icon>
