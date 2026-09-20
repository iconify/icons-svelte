<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2-pembiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2-pembiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lifebuoy-line" {...props}></Icon>
