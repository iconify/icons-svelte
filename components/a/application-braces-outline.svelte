<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5rqtinri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5rqtinri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:application-braces-outline" {...props}></Icon>
