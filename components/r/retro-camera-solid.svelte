<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpk6ggg_n.css';
import '../../css/n/ndqxj1bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpk6ggg_n"/><path class="ndqxj1bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:retro-camera-solid" {...props}></Icon>
