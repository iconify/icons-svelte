<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqy5s6rdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqy5s6rdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:pin-small" {...props}></Icon>
