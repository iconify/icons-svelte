<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw5gqqbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw5gqqbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pause-box-outline" {...props}></Icon>
