<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0u1h5bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0u1h5bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bolt" {...props}></Icon>
