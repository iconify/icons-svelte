<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7cqk3gaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7cqk3gaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-circle" {...props}></Icon>
