<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxrdn95ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxrdn95ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clapperboard-open-outline" {...props}></Icon>
