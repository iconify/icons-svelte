<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-g4q9p2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-g4q9p2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-heading-equal" {...props}></Icon>
