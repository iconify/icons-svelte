<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omzwo4lej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omzwo4lej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:info-card-line" {...props}></Icon>
