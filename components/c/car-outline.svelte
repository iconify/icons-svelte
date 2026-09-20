<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-rxrbbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-rxrbbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-outline" {...props}></Icon>
