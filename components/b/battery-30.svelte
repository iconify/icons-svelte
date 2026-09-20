<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar5dirryl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar5dirryl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-30" {...props}></Icon>
