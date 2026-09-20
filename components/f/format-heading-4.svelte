<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls9339kws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls9339kws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-heading-4" {...props}></Icon>
