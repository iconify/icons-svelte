<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p10ijsbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p10ijsbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:grok-xai" {...props}></Icon>
