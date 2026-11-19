<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuhp3qbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuhp3qbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dreamcast" {...props}></Icon>
