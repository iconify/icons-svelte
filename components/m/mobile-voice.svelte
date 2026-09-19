<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqfv87bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqfv87bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:mobile-voice" {...props}></Icon>
