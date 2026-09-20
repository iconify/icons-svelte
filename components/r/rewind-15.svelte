<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea1_mnhta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea1_mnhta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rewind-15" {...props}></Icon>
