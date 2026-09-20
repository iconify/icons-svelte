<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g18k1pb8p.css';
import '../../css/s/s4_j3-_9s.css';
import '../../css/i/i7sr6ubzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g18k1pb8p"/><path class="s4_j3-_9s"/><path class="i7sr6ubzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:image-solid" {...props}></Icon>
