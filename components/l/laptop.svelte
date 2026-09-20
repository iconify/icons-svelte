<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu6bqfbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu6bqfbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:laptop" {...props}></Icon>
