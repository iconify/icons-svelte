<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn5gwnb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn5gwnb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulb-multiple-off-outline" {...props}></Icon>
