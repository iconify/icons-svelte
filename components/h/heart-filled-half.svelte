<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj-o9e.css';
import '../../css/y/yi8b0f.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-30.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj-o9e"/><path class="yi8b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:heart-filled-half" {...props}></Icon>
