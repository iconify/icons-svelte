<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpo49bc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpo49bc6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:extension" {...props}></Icon>
