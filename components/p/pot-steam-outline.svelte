<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aytm96b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aytm96b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pot-steam-outline" {...props}></Icon>
