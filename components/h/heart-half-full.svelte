<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpe47b1df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpe47b1df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-half-full" {...props}></Icon>
