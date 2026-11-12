<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jit5hm-5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jit5hm-5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-flame" {...props}></Icon>
