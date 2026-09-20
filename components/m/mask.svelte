<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5z2czd5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5z2czd5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:mask" {...props}></Icon>
