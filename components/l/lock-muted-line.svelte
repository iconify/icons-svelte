<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7xr77kna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7xr77kna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:lock-muted-line" {...props}></Icon>
